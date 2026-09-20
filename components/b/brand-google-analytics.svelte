<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0gqm4bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0gqm4bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-google-analytics" {...props}></Icon>
