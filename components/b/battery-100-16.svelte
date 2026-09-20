<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffaginb4b.css';
import '../../css/i/i1z3osb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ffaginb4b"/><path class="i1z3osb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:battery-100-16" {...props}></Icon>
