<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3d_pybjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3d_pybjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ideal" {...props}></Icon>
