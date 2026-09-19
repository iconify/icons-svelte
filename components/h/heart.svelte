<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-90pibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="m-90pibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:heart" {...props}></Icon>
