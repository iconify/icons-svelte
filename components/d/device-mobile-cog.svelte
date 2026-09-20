<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo_m2acat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo_m2acat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-cog" {...props}></Icon>
