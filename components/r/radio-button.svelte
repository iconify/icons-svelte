<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv8i4385h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="pv8i4385h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:radio-button" {...props}></Icon>
