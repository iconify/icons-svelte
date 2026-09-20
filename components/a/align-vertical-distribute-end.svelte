<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpq1hhjvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpq1hhjvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-distribute-end" {...props}></Icon>
