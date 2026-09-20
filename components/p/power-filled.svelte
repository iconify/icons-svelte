<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0p1c05ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r0p1c05ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:power-filled" {...props}></Icon>
