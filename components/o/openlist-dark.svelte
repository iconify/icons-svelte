<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy2y_xbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy2y_xbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openlist-dark" {...props}></Icon>
