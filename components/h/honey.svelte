<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l24eq7b1k.css';
import '../../css/g/gyvowbb7z.css';
import '../../css/q/qzdx_s0vk.css';
import '../../css/j/jl-543bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l24eq7b1k"/><path class="gyvowbb7z"/><path class="qzdx_s0vk"/><path class="jl-543bif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:honey" {...props}></Icon>
