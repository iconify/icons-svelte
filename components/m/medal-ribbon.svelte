<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-mf2gvfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a-mf2gvfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:medal-ribbon" {...props}></Icon>
