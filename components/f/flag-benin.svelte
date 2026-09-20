<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dur0b2p3t.css';
import '../../css/h/h8ttso15c.css';
import '../../css/r/rmslx6b5x.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="h8ttso15c"/><path class="rmslx6b5x"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-benin" {...props}></Icon>
