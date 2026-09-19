<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgs_pek_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mgs_pek_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:flag" {...props}></Icon>
