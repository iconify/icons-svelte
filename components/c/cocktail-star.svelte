<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxknf4tak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxknf4tak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cocktail-star" {...props}></Icon>
