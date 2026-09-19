<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dms1fbzlt.css';
import '../../css/r/rxjk7ymwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dms1fbzlt"/><path class="rxjk7ymwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:raisedhandpartfingers" {...props}></Icon>
