<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejelqccgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejelqccgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-solid" {...props}></Icon>
