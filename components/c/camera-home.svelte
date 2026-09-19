<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxc6vr24n.css';
import '../../css/s/sor5e_3vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="mxc6vr24n"/><path class="sor5e_3vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:camera-home" {...props}></Icon>
