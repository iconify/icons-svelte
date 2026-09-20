<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds5xzyo8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ds5xzyo8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gatsby-dark" {...props}></Icon>
