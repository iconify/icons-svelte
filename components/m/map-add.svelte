<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdbf7hbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbf7hbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-add" {...props}></Icon>
