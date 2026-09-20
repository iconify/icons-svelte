<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_mutobdf.css';
import '../../css/x/x0zug3lhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_mutobdf"/><path class="x0zug3lhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-calendar-dark" {...props}></Icon>
