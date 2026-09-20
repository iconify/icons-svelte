<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phxi50m6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phxi50m6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-discount-outline" {...props}></Icon>
