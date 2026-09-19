<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lx_5d149v.css';
import '../../css/u/ufeb2vbkv.css';
import '../../css/v/v4hv1obkb.css';
import '../../css/p/p44v6xbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lx_5d149v"/><path class="ufeb2vbkv"/><path class="v4hv1obkb"/><path class="p44v6xbnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:bed" {...props}></Icon>
