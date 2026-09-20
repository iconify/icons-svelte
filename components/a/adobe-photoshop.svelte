<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctl9dy8me.css';
import '../../css/k/kq3mrbcfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctl9dy8me"/><path class="kq3mrbcfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-photoshop" {...props}></Icon>
