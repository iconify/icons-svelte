<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juuf-3-cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juuf-3-cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:plus-circle" {...props}></Icon>
