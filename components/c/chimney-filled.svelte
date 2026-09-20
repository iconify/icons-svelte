<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mid6vpnoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mid6vpnoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chimney-filled" {...props}></Icon>
