<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl3t2kb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rl3t2kb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paw-48" {...props}></Icon>
