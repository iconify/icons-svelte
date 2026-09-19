<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jasz3fyxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jasz3fyxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-bell" {...props}></Icon>
