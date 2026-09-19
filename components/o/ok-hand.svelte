<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luy7zjvha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="luy7zjvha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ok-hand" {...props}></Icon>
