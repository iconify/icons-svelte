<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hta9pob_h.css';
import '../../css/m/mlf7ptbhg.css';
import '../../css/i/ivmhlacxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="hta9pob_h"/><path class="mlf7ptbhg"/><path class="ivmhlacxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:house-up-fill" {...props}></Icon>
