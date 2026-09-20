<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhzw11g-c.css';
import '../../css/i/ijkguh_1b.css';
import '../../css/n/n1u92sbdk.css';
import '../../css/e/eqqzzhten.css';
import '../../css/h/h8wtp5bbt.css';
import '../../css/a/a7_tu1bll.css';
import '../../css/e/ecyv2sh7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bhzw11g-c"/><path class="ijkguh_1b"/><path class="n1u92sbdk"/><g class="eqqzzhten"><path class="h8wtp5bbt"/><path class="a7_tu1bll"/><path class="ecyv2sh7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:goose" {...props}></Icon>
