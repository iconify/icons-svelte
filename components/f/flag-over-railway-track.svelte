<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yla03qffw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yla03qffw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flag-over-railway-track" {...props}></Icon>
