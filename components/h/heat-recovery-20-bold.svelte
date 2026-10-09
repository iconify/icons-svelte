<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvlc-tsag.css';
import '../../css/d/d60aetbtw.css';
import '../../css/r/rcl7udk4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jvlc-tsag"/><path class="d60aetbtw"/><path class="rcl7udk4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-recovery-20-bold" {...props}></Icon>
