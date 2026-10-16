<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw6bgrrst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw6bgrrst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fumarole-48-bold" {...props}></Icon>
