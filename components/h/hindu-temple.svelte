<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2e6ehonk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p2e6ehonk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hindu-temple" {...props}></Icon>
