<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d16_u1b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d16_u1b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:haze-48-bold" {...props}></Icon>
