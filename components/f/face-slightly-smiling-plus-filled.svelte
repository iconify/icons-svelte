<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2rpnbqd.css';
import '../../css/q/qf40r3s6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eb2rpnbqd"/><path class="qf40r3s6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:face-slightly-smiling-plus-filled" {...props}></Icon>
