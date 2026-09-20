<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0l9zdeaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y0l9zdeaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-both-outline" {...props}></Icon>
