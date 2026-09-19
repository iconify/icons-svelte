<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk6pc0bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nk6pc0bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-outline" {...props}></Icon>
