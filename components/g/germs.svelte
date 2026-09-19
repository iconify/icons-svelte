<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rr9p5hlao.css';
import '../../css/e/eir-cobpl.css';
import '../../css/v/v-ax0bbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rr9p5hlao"/><path class="eir-cobpl"/><path class="v-ax0bbpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:germs" {...props}></Icon>
