<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epi0c1bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epi0c1bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bulletlist" {...props}></Icon>
