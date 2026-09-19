<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0mt9cwce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0mt9cwce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:apps-light" {...props}></Icon>
