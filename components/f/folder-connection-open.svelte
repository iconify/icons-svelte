<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up2j63u8p.css';
import '../../css/q/qu-z_obdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="up2j63u8p"/><path class="qu-z_obdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-connection-open" {...props}></Icon>
