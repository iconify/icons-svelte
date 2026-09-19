<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxyo3ya3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxyo3ya3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-water" {...props}></Icon>
