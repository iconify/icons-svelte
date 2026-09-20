<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6uw3rb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n6uw3rb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:quran" {...props}></Icon>
