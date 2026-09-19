<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5m-s_bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y5m-s_bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:csw" {...props}></Icon>
