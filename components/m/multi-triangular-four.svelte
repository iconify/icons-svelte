<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0embdbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n0embdbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:multi-triangular-four" {...props}></Icon>
