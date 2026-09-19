<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0c0xbc1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n0c0xbc1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:dagger" {...props}></Icon>
