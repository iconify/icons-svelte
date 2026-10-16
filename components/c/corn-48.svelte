<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5i0nibgo.css';
import '../../css/h/hmt9evbnn.css';
import '../../css/w/we9u0mx2s.css';
import '../../css/a/atyhtibwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r5i0nibgo"/><path class="hmt9evbnn"/><path class="we9u0mx2s"/><path class="atyhtibwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corn-48" {...props}></Icon>
