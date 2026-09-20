<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htmjl2bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htmjl2bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-drawing" {...props}></Icon>
