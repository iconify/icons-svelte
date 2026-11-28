<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lys6u4jad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lys6u4jad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book" {...props}></Icon>
