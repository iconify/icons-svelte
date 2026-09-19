<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dix9hbbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dix9hbbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:cocktail-glass" {...props}></Icon>
