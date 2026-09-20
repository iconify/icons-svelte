<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4jw8wbpz.css';
import '../../css/j/jxqi2jbpi.css';
import '../../css/i/i3kk-g2-z.css';
import '../../css/j/j55quss0c.css';
import '../../css/j/j5h59ccev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="f4jw8wbpz"/><g class="jxqi2jbpi"><circle class="i3kk-g2-z"/><path class="j55quss0c"/><circle class="j5h59ccev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:radioactive" {...props}></Icon>
