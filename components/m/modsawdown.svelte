<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xupllvb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xupllvb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:modsawdown" {...props}></Icon>
