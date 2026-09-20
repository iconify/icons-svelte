<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihurembfg.css';
import '../../css/d/doj9dq_jg.css';
import '../../css/b/bepahm04n.css';
import '../../css/j/jimrxwnfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ihurembfg"/><g class="doj9dq_jg"><path class="bepahm04n"/><path class="jimrxwnfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cloud-with-snow" {...props}></Icon>
