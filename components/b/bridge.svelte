<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2n3pfxid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2n3pfxid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bridge" {...props}></Icon>
