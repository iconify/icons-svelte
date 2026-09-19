<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcktnkb4m.css';
import '../../css/q/q6m--wbvm.css';
import '../../css/d/dhms69pem.css';
import '../../css/e/e_ohi9xtb.css';
import '../../css/m/m0h17nkyl.css';
import '../../css/j/jo39ibclw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mcktnkb4m"/><path class="q6m--wbvm"/><path class="dhms69pem"/><path class="e_ohi9xtb"/><path class="m0h17nkyl"/><path class="jo39ibclw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:gpa" {...props}></Icon>
