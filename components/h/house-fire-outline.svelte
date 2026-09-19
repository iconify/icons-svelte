<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_dq43bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w_dq43bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-fire-outline" {...props}></Icon>
