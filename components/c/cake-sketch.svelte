<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ywqlgrn8l.css';
import '../../css/a/ax_f3jbbk.css';
import '../../css/a/a900ikb8p.css';
import '../../css/a/a6785dwqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k ywqlgrn8l"/><path class="ax_f3jbbk wm-a"/><path class="a900ikb8p wm-k"/><path class="a6785dwqv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cake-sketch" {...props}></Icon>
