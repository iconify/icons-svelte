<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs82pv97p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qs82pv97p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-sm-stroke-16" {...props}></Icon>
