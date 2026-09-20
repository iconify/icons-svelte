<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orb8mhbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="orb8mhbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:medium" {...props}></Icon>
