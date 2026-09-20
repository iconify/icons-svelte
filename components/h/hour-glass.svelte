<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aafoxqbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aafoxqbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:hour-glass" {...props}></Icon>
