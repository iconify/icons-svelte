<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv2c6vbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv2c6vbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mop-filled" {...props}></Icon>
