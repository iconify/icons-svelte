<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuy18qpjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kuy18qpjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-barrel-1-level" {...props}></Icon>
