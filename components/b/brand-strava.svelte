<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0abgbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0abgbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-strava" {...props}></Icon>
