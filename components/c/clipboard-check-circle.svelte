<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jtpr1vq3n.css';
import '../../css/r/rwch1289m.css';
import '../../css/q/q9xupgbzh.css';
import '../../css/g/g7rc37bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jtpr1vq3n"/><path class="rwch1289m"/><path class="q9xupgbzh"/><path class="g7rc37bep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:clipboard-check-circle" {...props}></Icon>
