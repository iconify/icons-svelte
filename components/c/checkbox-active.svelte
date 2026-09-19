<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5sxvgbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="m5sxvgbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:checkbox-active" {...props}></Icon>
