<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckolh8b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ckolh8b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:horizon-alt" {...props}></Icon>
