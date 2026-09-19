<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2uncfcru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m2uncfcru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:black-nib" {...props}></Icon>
