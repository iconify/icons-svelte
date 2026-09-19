<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij74tbbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ij74tbbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:atlas" {...props}></Icon>
