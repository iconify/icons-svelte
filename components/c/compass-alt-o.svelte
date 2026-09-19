<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqcxf6bxf.css';
import '../../css/b/b13va5b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vqcxf6bxf"/><path class="b13va5b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:compass-alt-o" {...props}></Icon>
