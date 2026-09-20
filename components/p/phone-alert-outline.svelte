<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfamm1_av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfamm1_av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-alert-outline" {...props}></Icon>
