<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id8ppqfji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id8ppqfji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:pin" {...props}></Icon>
