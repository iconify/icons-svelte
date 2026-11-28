<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj-cb-bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rj-cb-bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:helicopter-light" {...props}></Icon>
