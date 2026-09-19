<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7-j0_rby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m7-j0_rby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:prohibited" {...props}></Icon>
