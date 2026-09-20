<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub3v3v1ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub3v3v1ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:checkbox-on" {...props}></Icon>
