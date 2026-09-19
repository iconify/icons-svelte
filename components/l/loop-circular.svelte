<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms9_73-iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms9_73-iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:loop-circular" {...props}></Icon>
