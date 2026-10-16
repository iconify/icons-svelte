<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6hwt2o8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":115.333,"height":114};
const content = `<path class="r6hwt2o8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alertmanager" {...props}></Icon>
