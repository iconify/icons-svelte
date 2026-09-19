<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izlo61v6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="izlo61v6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:flip-h" {...props}></Icon>
