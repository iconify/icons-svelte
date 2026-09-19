<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0i0_d7-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v0i0_d7-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:burst" {...props}></Icon>
