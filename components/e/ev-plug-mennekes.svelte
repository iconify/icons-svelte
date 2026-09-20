<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd46vfgmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd46vfgmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ev-plug-mennekes" {...props}></Icon>
