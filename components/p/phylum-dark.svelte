<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5q7p6dir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v5q7p6dir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phylum-dark" {...props}></Icon>
