<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpmwkf-7z.css';
import '../../css/f/fl2kpnyol.css';
import '../../css/w/wk6b4ib4t.css';
import '../../css/u/u28u1dcvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpmwkf-7z"/><path class="fl2kpnyol"/><path class="wk6b4ib4t"/><path class="u28u1dcvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plate-bold-duotone" {...props}></Icon>
