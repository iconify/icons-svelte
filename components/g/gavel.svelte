<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdj1o0xsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdj1o0xsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gavel" {...props}></Icon>
