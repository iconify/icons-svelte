<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w10-y0b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":152,"height":432};
const content = `<path class="w10-y0b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:male-alt" {...props}></Icon>
