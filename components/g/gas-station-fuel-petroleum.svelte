<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rjb4sd8ra.css';
import '../../css/r/rcvcc1uju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rjb4sd8ra"/><path class="rcvcc1uju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gas-station-fuel-petroleum" {...props}></Icon>
