<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwpc3spew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwpc3spew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project" {...props}></Icon>
