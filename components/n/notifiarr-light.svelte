<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7hyltcif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7hyltcif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notifiarr-light" {...props}></Icon>
