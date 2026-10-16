<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1aumdb7c.css';
import '../../css/k/kw01wubkh.css';
import '../../css/w/w0gkibbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i1aumdb7c"/><path class="kw01wubkh"/><path class="w0gkibbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-source-20-bold" {...props}></Icon>
