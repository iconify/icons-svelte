<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qas2_abke.css';
import '../../css/j/jn8y3-sdj.css';
import '../../css/o/okvup7g4x.css';
import '../../css/r/rcrg1izib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qas2_abke"/><path clip-rule="evenodd" class="jn8y3-sdj"/><path class="okvup7g4x"/><path clip-rule="evenodd" class="rcrg1izib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:fast-forward" {...props}></Icon>
