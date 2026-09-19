<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo4chr_jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo4chr_jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-data" {...props}></Icon>
