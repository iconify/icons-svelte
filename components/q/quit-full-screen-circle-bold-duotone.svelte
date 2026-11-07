<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/i/ijzot5blw.css';
import '../../css/i/ilfmvncty.css';
import '../../css/s/swg6q8buh.css';
import '../../css/n/ngp5n-n4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="ijzot5blw"/><path class="ilfmvncty"/><path class="swg6q8buh"/><path class="ngp5n-n4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-circle-bold-duotone" {...props}></Icon>
