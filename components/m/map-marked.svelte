<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd2e8acga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cd2e8acga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-marked" {...props}></Icon>
