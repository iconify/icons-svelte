<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i29phwzfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i29phwzfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-remove-fill-12" {...props}></Icon>
