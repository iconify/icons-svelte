<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmxejubuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jmxejubuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orb-light" {...props}></Icon>
