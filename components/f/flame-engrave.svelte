<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/klnli2bzd.css';
import '../../css/o/oeui3wblq.css';
import '../../css/l/lb5z5tb2v.css';
import '../../css/b/bmlr6ob0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="klnli2bzd wm-k"/><path class="oeui3wblq wm-shadow"/><path class="lb5z5tb2v wm-k"/><path class="bmlr6ob0i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flame-engrave" {...props}></Icon>
