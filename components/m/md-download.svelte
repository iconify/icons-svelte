<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy-z67b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uy-z67b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-download" {...props}></Icon>
