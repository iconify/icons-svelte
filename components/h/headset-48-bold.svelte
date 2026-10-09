<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr8phfb8h.css';
import '../../css/u/uyuy9qbxm.css';
import '../../css/v/vfxz7qx3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jr8phfb8h"/><path class="uyuy9qbxm"/><path class="vfxz7qx3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headset-48-bold" {...props}></Icon>
