<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz2g28hhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lz2g28hhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airport-plane" {...props}></Icon>
