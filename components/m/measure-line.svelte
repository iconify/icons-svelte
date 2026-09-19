<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1gavvj8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="u1gavvj8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:measure-line" {...props}></Icon>
