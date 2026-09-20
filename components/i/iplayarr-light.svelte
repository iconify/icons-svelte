<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6bpd94xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6bpd94xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iplayarr-light" {...props}></Icon>
