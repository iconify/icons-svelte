<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djix0pbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="djix0pbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:axe" {...props}></Icon>
