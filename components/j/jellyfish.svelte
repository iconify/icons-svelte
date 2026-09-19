<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3j32evkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d3j32evkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:jellyfish" {...props}></Icon>
