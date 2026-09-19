<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clsdao61r.css';
import '../../css/o/o0bilwbsi.css';
import '../../css/r/rlsf7gb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="o0bilwbsi"/><path class="rlsf7gb6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:groovy" {...props}></Icon>
