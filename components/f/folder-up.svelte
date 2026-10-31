<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/djhr1bb5p.css';
import '../../css/p/p49sfo0gg.css';
import '../../css/y/y-o7ms42k.css';
import '../../css/p/pe0rmb8ad.css';
import '../../css/r/rt9v9sb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="djhr1bb5p wm-k"/><path class="p49sfo0gg wm-shine"/><path class="wm-shine y-o7ms42k"/><path class="pe0rmb8ad wm-shine"/><path class="rt9v9sb0t wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:folder-up" {...props}></Icon>
