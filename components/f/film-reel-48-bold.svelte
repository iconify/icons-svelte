<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw6oy3bzc.css';
import '../../css/m/m-5n_6hvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xw6oy3bzc"/><path class="m-5n_6hvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-reel-48-bold" {...props}></Icon>
