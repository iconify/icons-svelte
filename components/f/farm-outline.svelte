<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkibnmmcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkibnmmcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:farm-outline" {...props}></Icon>
