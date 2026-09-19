<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5f6eyvtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5f6eyvtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:crab" {...props}></Icon>
