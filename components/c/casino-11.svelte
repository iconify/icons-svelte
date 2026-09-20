<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdsyclb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="pdsyclb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:casino-11" {...props}></Icon>
