<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka0ey-ttx.css';
import '../../css/u/uclife8yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ka0ey-ttx"/><path class="uclife8yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-48-bold" {...props}></Icon>
