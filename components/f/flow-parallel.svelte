<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anhxi-3cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="anhxi-3cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flow-parallel" {...props}></Icon>
