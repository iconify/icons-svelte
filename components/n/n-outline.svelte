<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2ofdew1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l2ofdew1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:n-outline" {...props}></Icon>
