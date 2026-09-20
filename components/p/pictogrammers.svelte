<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6_3-mbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u6_3-mbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pictogrammers" {...props}></Icon>
