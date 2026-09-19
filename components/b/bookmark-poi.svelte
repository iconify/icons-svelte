<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie9k28r9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ie9k28r9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:bookmark-poi" {...props}></Icon>
