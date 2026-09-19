<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoksj6-5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="xoksj6-5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:rectangle-outline" {...props}></Icon>
