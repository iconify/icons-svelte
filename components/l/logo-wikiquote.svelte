<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkjsnojvf.css';
import '../../css/h/hrl1fmafq.css';
import '../../css/c/c4s-zobzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zkjsnojvf"/><path class="hrl1fmafq"/><circle class="c4s-zobzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikiquote" {...props}></Icon>
