<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3oyxk-jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3oyxk-jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-right-broken" {...props}></Icon>
