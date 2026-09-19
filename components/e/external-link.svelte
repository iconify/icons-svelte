<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_qw5gr9p.css';
import '../../css/y/yrfreqb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_qw5gr9p"/><path class="yrfreqb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:external-link" {...props}></Icon>
