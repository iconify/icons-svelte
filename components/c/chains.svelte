<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km_57-b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="km_57-b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:chains" {...props}></Icon>
