<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1yv9abga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1yv9abga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-to-left" {...props}></Icon>
