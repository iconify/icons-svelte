<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjjddbshj.css';
import '../../css/f/flc82qukb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rjjddbshj"/><path class="flc82qukb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crop-48" {...props}></Icon>
