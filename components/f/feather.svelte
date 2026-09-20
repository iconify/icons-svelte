<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v37_dyb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v37_dyb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:feather" {...props}></Icon>
