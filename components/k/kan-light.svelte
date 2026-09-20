<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sisk_ebgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sisk_ebgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kan-light" {...props}></Icon>
