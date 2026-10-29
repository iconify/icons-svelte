<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sortblb2j.css';
import '../../css/w/w-5rgdbpk.css';
import '../../css/a/avwj5pu0c.css';
import '../../css/j/j74ghonra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sortblb2j wm-k"/><path class="w-5rgdbpk wm-a"/><path class="avwj5pu0c wm-k"/><path class="j74ghonra wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:case-upper-sketch" {...props}></Icon>
