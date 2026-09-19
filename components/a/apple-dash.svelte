<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x06e9_b2c.css';
import '../../css/x/xg13r0bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x06e9_b2c"/><path class="xg13r0bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:apple-dash" {...props}></Icon>
