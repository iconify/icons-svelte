<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv_-ltgmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sv_-ltgmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeradius-light" {...props}></Icon>
