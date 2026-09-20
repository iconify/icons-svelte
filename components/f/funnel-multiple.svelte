<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz31xb1hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz31xb1hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:funnel-multiple" {...props}></Icon>
