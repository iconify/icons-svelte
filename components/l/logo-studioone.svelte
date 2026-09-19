<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x70ytk24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x70ytk24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-studioone" {...props}></Icon>
