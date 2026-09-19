<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/r/rj75s3mpj.css';
import '../../css/a/at3qv7bjo.css';
import '../../css/q/q6p4_jbmf.css';
import '../../css/g/gw9ia0bov.css';
import '../../css/d/djg0w9bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="rj75s3mpj"/><path class="at3qv7bjo"/><path class="q6p4_jbmf"/><path class="gw9ia0bov"/><path class="djg0w9bxu"/><line x1="20" x2="20" y1="27" y2="44"/><line x1="28" x2="28" y1="27" y2="44"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cake-five" {...props}></Icon>
