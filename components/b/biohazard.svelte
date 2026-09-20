<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4jw8wbpz.css';
import '../../css/b/bnnoq8bqn.css';
import '../../css/e/ejqbi5b-l.css';
import '../../css/i/i3ff7jbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="f4jw8wbpz"/><circle class="bnnoq8bqn"/><path class="ejqbi5b-l"/><path class="i3ff7jbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:biohazard" {...props}></Icon>
