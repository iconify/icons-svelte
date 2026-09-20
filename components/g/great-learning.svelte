<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwv2phcpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwv2phcpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:great-learning" {...props}></Icon>
