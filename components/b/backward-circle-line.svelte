<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j-46ttn1w.css';
import '../../css/u/uxh9_acgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle transform="matrix(-1 0 0 1 12 12)" class="j-46ttn1w"/><path class="uxh9_acgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:backward-circle-line" {...props}></Icon>
