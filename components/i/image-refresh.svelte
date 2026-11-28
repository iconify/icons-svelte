<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfdi84ohu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfdi84ohu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-refresh" {...props}></Icon>
