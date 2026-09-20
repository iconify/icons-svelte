<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy7_yfvvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7_yfvvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:menu-circle" {...props}></Icon>
