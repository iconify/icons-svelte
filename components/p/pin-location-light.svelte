<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqlbbubhn.css';
import '../../css/n/ngbp4qb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqlbbubhn"/><path class="ngbp4qb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-location-light" {...props}></Icon>
