<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcyedxxtq.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/p/pyhwdlbaj.css';
import '../../css/f/fk9ervbqx.css';
import '../../css/c/cfi22q2gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jcyedxxtq"/><g class="jn8qy4bru"><path class="pyhwdlbaj"/><path class="fk9ervbqx"/><path class="cfi22q2gr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fingerprint" {...props}></Icon>
