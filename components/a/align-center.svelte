<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cypfrkb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cypfrkb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:align-center" {...props}></Icon>
