<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlf7ptbhg.css';
import '../../css/d/dv9h9fbnb.css';
import '../../css/m/mbbf06b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mlf7ptbhg"/><path class="dv9h9fbnb"/><path class="mbbf06b8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:house-lock-fill" {...props}></Icon>
