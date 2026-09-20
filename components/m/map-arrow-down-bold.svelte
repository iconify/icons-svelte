<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oolfl0bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oolfl0bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-down-bold" {...props}></Icon>
