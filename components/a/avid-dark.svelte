<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r95xtcble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":193.2,"height":58.2};
const content = `<path class="r95xtcble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avid-dark" {...props}></Icon>
