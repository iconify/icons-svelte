<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv4k_bcjk.css';
import '../../css/c/c62utbkso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dv4k_bcjk"/><path class="c62utbkso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-area-48" {...props}></Icon>
