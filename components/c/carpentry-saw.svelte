<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjh7xxbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hjh7xxbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:carpentry-saw" {...props}></Icon>
