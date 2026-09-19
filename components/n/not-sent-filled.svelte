<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tile2lekl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tile2lekl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:not-sent-filled" {...props}></Icon>
