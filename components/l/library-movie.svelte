<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhz0znglf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhz0znglf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:library-movie" {...props}></Icon>
