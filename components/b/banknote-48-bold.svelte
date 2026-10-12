<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ejkab4k.css';
import '../../css/l/l54utlx8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r9ejkab4k"/><path class="l54utlx8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:banknote-48-bold" {...props}></Icon>
