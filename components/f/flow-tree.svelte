<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8tn3nbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m8tn3nbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flow-tree" {...props}></Icon>
