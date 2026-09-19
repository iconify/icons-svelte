<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esoy3w7su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="esoy3w7su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:qgis" {...props}></Icon>
