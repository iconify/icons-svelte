<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu20-2boz.css';
import '../../css/s/snl0_-vqu.css';
import '../../css/j/jurtbe_bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xu20-2boz"/><path class="snl0_-vqu"/><path class="jurtbe_bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-output-20-bold" {...props}></Icon>
