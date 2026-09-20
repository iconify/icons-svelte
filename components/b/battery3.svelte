<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rom9c69aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rom9c69aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battery3" {...props}></Icon>
