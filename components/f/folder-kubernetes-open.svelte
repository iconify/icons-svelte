<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/a/a41wlnb0g.css';
import '../../css/t/tzzto2buw.css';
import '../../css/q/qmyrkab0o.css';
import '../../css/l/l02npbdcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="a41wlnb0g"/><g class="tzzto2buw"><circle class="qmyrkab0o"/><path class="l02npbdcr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-kubernetes-open" {...props}></Icon>
