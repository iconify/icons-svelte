<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-1yv-bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-1yv-bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openfga-dark" {...props}></Icon>
