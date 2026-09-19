<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuv7dvbxa.css';
import '../../css/f/fvzirrn2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuv7dvbxa"/><path class="fvzirrn2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hdmi" {...props}></Icon>
