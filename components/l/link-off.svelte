<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpo-87w4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="kpo-87w4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:link-off" {...props}></Icon>
