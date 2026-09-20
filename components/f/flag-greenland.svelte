<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkq7-hbwz.css';
import '../../css/h/h8ttso15c.css';
import '../../css/g/gczwk7b2i.css';
import '../../css/q/qan60rbsg.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="h8ttso15c"/><circle class="gczwk7b2i"/><path class="qan60rbsg"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-greenland" {...props}></Icon>
