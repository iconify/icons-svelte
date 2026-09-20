<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-tkx6bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-tkx6bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:camera-add" {...props}></Icon>
