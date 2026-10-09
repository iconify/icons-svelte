<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crgylcbgx.css';
import '../../css/j/j_uf38bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="crgylcbgx"/><path class="j_uf38bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-location-20" {...props}></Icon>
