<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nta6gac4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="nta6gac4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-forward" {...props}></Icon>
