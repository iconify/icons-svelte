<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlf7ptbhg.css';
import '../../css/i/ivmhlacxz.css';
import '../../css/w/wklmn_zku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mlf7ptbhg"/><path class="ivmhlacxz"/><path class="wklmn_zku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:house-slash-fill" {...props}></Icon>
