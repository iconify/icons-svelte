<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfe-tv.css';
import '../../css/s/s8e22g.css';
import '../../css/z/z5tiej.css';
import '../../css/d/d-vg0s0b.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfe-tv s8e22g"/><path class="s8e22g z5tiej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:patreon" {...props}></Icon>
