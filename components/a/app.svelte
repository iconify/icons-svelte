<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcq1h3pnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wcq1h3pnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:app" {...props}></Icon>
