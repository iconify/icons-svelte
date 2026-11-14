<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lirut0xsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lirut0xsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-01" {...props}></Icon>
