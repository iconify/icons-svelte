<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlvw76bka.css';
import '../../css/u/uwlyphbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dlvw76bka"/><path class="uwlyphbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-egg" {...props}></Icon>
