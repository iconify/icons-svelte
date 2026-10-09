<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0140xb6z.css';
import '../../css/v/v-c6wh_lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t0140xb6z"/><path class="v-c6wh_lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-right-48" {...props}></Icon>
