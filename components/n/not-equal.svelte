<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgpy0vwps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wgpy0vwps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:not-equal" {...props}></Icon>
