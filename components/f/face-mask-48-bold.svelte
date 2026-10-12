<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr0py_b6k.css';
import '../../css/x/xuyp_ezqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zr0py_b6k"/><path class="xuyp_ezqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-mask-48-bold" {...props}></Icon>
