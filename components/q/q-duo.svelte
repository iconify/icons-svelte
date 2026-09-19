<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or8-05bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="or8-05bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:q-duo" {...props}></Icon>
