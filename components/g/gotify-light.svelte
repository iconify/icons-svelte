<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jza233_yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jza233_yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotify-light" {...props}></Icon>
