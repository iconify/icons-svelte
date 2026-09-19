<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utvslpn-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="utvslpn-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-left-circle" {...props}></Icon>
