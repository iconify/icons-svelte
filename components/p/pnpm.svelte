<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/c/chico6sfv.css';
import '../../css/w/wuh5h2bwt.css';
import '../../css/s/stgp-sogn.css';
import '../../css/p/pa9ny6bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="chico6sfv"/><path class="wuh5h2bwt"/><path class="stgp-sogn"/><path class="pa9ny6bge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:pnpm" {...props}></Icon>
