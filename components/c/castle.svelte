<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k0phntbpf.css';
import '../../css/f/f78qppjnj.css';
import '../../css/g/g_i87xbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k0phntbpf"/><path class="f78qppjnj"/><path class="g_i87xbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:castle" {...props}></Icon>
