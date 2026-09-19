<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/w/w_6x2gb8n.css';
import '../../css/l/laf36ebwr.css';
import '../../css/j/jo097xb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="w_6x2gb8n"/><path class="laf36ebwr"/><path class="jo097xb2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:julia" {...props}></Icon>
