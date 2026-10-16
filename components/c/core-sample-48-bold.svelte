<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0tg29byf.css';
import '../../css/u/uy3553_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0tg29byf"/><path class="uy3553_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:core-sample-48-bold" {...props}></Icon>
