<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arknlwboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="arknlwboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:c-outline" {...props}></Icon>
