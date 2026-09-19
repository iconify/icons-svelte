<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzkxxlbjg.css';
import '../../css/t/t_2lkqbxb.css';
import '../../css/h/hablheomi.css';
import '../../css/c/c_g70-55x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zzkxxlbjg"/><g class="t_2lkqbxb"><path class="hablheomi"/><path class="c_g70-55x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-caddy" {...props}></Icon>
