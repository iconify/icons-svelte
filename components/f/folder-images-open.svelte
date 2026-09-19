<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/a/a41wlnb0g.css';
import '../../css/g/gblnf2b1i.css';
import '../../css/x/x6kf_nbul.css';
import '../../css/l/l6cagebmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="a41wlnb0g"/><path class="gblnf2b1i"/><path class="x6kf_nbul"/><circle class="l6cagebmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-images-open" {...props}></Icon>
