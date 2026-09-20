<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs0c_5blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs0c_5blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-left-bold" {...props}></Icon>
