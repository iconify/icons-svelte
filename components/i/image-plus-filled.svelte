<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm3xqsybe.css';
import '../../css/q/qf40r3s6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rm3xqsybe"/><path class="qf40r3s6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-plus-filled" {...props}></Icon>
