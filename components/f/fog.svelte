<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdd35gb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pdd35gb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fog" {...props}></Icon>
