<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfe3tgbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfe3tgbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-cat" {...props}></Icon>
