<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkf55sbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vkf55sbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laugh-squint-bold" {...props}></Icon>
