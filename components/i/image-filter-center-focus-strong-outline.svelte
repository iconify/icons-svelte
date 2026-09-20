<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2r6r_wuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2r6r_wuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-center-focus-strong-outline" {...props}></Icon>
