<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw4-4_bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uw4-4_bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hammer" {...props}></Icon>
