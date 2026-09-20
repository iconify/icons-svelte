<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuc69jbme.css';
import '../../css/x/x6q1qsb4x.css';
import '../../css/f/f6l_3qegk.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/djiglgypw.css';
import '../../css/g/g8q-87bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nuc69jbme"/><circle class="x6q1qsb4x"/><path class="f6l_3qegk"/><g class="jn8qy4bru"><path class="djiglgypw"/><path class="g8q-87bvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:github" {...props}></Icon>
