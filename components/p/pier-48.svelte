<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz0wpbbiw.css';
import '../../css/m/mah8bbc0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sz0wpbbiw"/><path class="mah8bbc0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pier-48" {...props}></Icon>
