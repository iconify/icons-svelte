<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9_5pv2nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9_5pv2nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-recording" {...props}></Icon>
