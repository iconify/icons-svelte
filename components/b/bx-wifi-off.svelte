<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnd6bg8sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnd6bg8sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wifi-off" {...props}></Icon>
