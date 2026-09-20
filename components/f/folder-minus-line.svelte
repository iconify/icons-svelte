<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt-x7st9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt-x7st9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-minus-line" {...props}></Icon>
