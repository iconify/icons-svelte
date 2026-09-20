<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu9465z8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="nu9465z8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pickaxe" {...props}></Icon>
