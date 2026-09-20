<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpbjpac9g.css';
import '../../css/k/kgf0r7bvp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/i/ihxzzib8n.css';
import '../../css/h/h9t1rz7uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cpbjpac9g"/><path class="kgf0r7bvp"/><g class="jn8qy4bru"><path class="ihxzzib8n"/><path class="h9t1rz7uy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:kite" {...props}></Icon>
