<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0gxa7bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0gxa7bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:plus-expressive" {...props}></Icon>
