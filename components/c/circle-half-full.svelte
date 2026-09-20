<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz4ul3vvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz4ul3vvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-half-full" {...props}></Icon>
