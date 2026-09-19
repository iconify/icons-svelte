<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptk_gpb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ptk_gpb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-0" {...props}></Icon>
