<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn5-me7co.css';
import '../../css/x/xpeiq2kly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zn5-me7co"/><path class="xpeiq2kly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-star" {...props}></Icon>
