<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd9v2eb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd9v2eb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:location-arrow" {...props}></Icon>
