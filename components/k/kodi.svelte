<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqte5-ewe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqte5-ewe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kodi" {...props}></Icon>
