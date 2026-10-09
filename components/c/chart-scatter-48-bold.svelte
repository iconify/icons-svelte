<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y--jnj11k.css';
import '../../css/k/kqp7h7bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y--jnj11k"/><path class="kqp7h7bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-scatter-48-bold" {...props}></Icon>
