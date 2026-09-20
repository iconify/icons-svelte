<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1uhn8dbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c1uhn8dbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sliding-on-cliff-into-water" {...props}></Icon>
