<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbh1lyi-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbh1lyi-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-spline-solid" {...props}></Icon>
