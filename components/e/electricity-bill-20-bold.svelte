<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8_piicxj.css';
import '../../css/n/nvkdiwbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8_piicxj"/><path class="nvkdiwbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electricity-bill-20-bold" {...props}></Icon>
