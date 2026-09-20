<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpif0vp-i.css';
import '../../css/v/vd05wq3fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpif0vp-i"/><path class="vd05wq3fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-assistant-matter-hub" {...props}></Icon>
