<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sow3prfxe.css';
import '../../css/c/c673ry-kp.css';
import '../../css/x/xfbl9fbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sow3prfxe"/><path class="c673ry-kp"/><path class="xfbl9fbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloche-48" {...props}></Icon>
