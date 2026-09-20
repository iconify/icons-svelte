<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm9jy4ulr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm9jy4ulr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-open-cog" {...props}></Icon>
