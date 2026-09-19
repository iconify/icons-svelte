<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed9qujb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ed9qujb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:difference" {...props}></Icon>
