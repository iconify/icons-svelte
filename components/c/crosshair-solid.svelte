<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkeux50xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkeux50xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:crosshair-solid" {...props}></Icon>
