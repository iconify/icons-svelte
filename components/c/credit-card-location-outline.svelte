<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1y9ezbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1y9ezbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-location-outline" {...props}></Icon>
