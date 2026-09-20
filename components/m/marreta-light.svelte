<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdpi_bbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdpi_bbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marreta-light" {...props}></Icon>
