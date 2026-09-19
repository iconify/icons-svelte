<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/websu8mzr.css';
import '../../css/j/jdo911b9f.css';
import '../../css/a/a0wcmjm3e.css';
import '../../css/o/oxqq_4bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="websu8mzr"/><path class="jdo911b9f"/><path class="a0wcmjm3e"/><path class="oxqq_4bxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:football" {...props}></Icon>
