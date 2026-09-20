<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynjlvfb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynjlvfb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-justify-center" {...props}></Icon>
