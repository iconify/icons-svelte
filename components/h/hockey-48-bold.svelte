<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh00p_b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hh00p_b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hockey-48-bold" {...props}></Icon>
