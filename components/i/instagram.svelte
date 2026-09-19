<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/myry6db3q.css';
import '../../css/w/w1li8bbqj.css';
import '../../css/n/n0-4s7bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="myry6db3q"/><path class="w1li8bbqj"/><path class="n0-4s7bet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:instagram" {...props}></Icon>
