<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/b0o513hwu.css';
import '../../css/k/k_88nvj7z.css';
import '../../css/g/gly7u_bza.css';
import '../../css/f/frhleablc.css';
import '../../css/o/o2t9r1bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="b0o513hwu"/><path class="k_88nvj7z"/><path class="gly7u_bza"/><path class="frhleablc"/><path class="o2t9r1bbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:low-vision-outline" {...props}></Icon>
