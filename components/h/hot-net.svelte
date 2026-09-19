<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5wl3gvdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5wl3gvdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hot-net" {...props}></Icon>
