<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivh42bn2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="ivh42bn2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:refresh-sync" {...props}></Icon>
