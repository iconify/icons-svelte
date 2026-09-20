<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjafxw1gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rjafxw1gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mute" {...props}></Icon>
