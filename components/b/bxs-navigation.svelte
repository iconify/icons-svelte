<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0cgfdb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0cgfdb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-navigation" {...props}></Icon>
