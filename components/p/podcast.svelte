<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz3f5jbrh.css';
import '../../css/y/yszcp8i3o.css';
import '../../css/b/bhdojms-k.css';
import '../../css/m/mj_kz-61s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dz3f5jbrh"/><path class="yszcp8i3o"/><path class="bhdojms-k"/><path class="mj_kz-61s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:podcast" {...props}></Icon>
