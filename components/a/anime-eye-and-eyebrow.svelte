<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6fhxyvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v6fhxyvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anime-eye-and-eyebrow" {...props}></Icon>
