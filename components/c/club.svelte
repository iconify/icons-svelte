<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr_fj5b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sr_fj5b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:club" {...props}></Icon>
