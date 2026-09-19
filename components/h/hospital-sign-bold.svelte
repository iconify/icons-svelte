<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhp55-bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nhp55-bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hospital-sign-bold" {...props}></Icon>
