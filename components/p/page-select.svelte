<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcxsgkb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcxsgkb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:page-select" {...props}></Icon>
