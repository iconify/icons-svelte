<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/h/hio0vubtf.css';
import '../../css/m/mwn4fp5kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="hio0vubtf"/><path class="mwn4fp5kw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:linkedin" {...props}></Icon>
