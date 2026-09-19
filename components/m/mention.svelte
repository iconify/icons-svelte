<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/c/c3ctpngqm.css';
import '../../css/s/s4r7xqb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="aqhok2bbj"/><path class="c3ctpngqm"/><path class="s4r7xqb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:mention" {...props}></Icon>
