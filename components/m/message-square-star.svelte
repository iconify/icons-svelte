<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxyfuiwlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxyfuiwlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-square-star" {...props}></Icon>
