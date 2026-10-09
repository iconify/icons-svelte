<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mml-20uch.css';
import '../../css/e/e80us0jnl.css';
import '../../css/t/t9qlqybcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mml-20uch"/><path class="e80us0jnl"/><path class="t9qlqybcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ferris-wheel-48" {...props}></Icon>
