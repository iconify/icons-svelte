<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6r7z_bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6r7z_bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bootstrap" {...props}></Icon>
