<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzvqo1krd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xzvqo1krd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-outline" {...props}></Icon>
