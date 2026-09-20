<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8kz08b1o.css';
import '../../css/x/xl0flj30v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i8kz08b1o"/><path class="xl0flj30v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:eye" {...props}></Icon>
