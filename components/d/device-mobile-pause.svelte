<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssvs6gz7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssvs6gz7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-pause" {...props}></Icon>
