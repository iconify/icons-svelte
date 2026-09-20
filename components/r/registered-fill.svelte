<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcpn8ebbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcpn8ebbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:registered-fill" {...props}></Icon>
