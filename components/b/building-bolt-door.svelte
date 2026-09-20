<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0e4x_mua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f0e4x_mua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:building-bolt-door" {...props}></Icon>
