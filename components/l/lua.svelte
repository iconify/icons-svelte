<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/c/c3ht4cb9b.css';
import '../../css/b/b0_jwbcxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="c3ht4cb9b"/><path class="b0_jwbcxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:lua" {...props}></Icon>
