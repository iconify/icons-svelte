<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhdef1ytm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhdef1ytm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:autobrr-light" {...props}></Icon>
