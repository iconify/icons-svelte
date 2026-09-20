<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_p-8obpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_p-8obpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-star" {...props}></Icon>
