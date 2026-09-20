<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozbufubkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozbufubkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openhab-light" {...props}></Icon>
