<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmzcjlsck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmzcjlsck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:backup-outline" {...props}></Icon>
