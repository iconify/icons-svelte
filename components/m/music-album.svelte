<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_hn_bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jl_hn_bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:music-album" {...props}></Icon>
