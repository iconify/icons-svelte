<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3vt5_b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3vt5_b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:arrow-right" {...props}></Icon>
