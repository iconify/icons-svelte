<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfxe2qbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hfxe2qbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:btc" {...props}></Icon>
