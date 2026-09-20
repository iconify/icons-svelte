<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmk4btbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmk4btbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gatsby-light" {...props}></Icon>
