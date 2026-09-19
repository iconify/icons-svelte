<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhspiezwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qhspiezwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:d-outline" {...props}></Icon>
