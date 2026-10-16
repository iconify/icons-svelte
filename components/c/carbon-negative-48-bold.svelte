<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlyerkbto.css';
import '../../css/u/u0bew_y1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vlyerkbto"/><path class="u0bew_y1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-negative-48-bold" {...props}></Icon>
