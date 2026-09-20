<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wism3vaym.css';
import '../../css/v/vrch38b1p.css';
import '../../css/r/rrfyfxb_f.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="vrch38b1p"/><path class="rrfyfxb_f"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-bulgaria" {...props}></Icon>
