<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpa12j_nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rpa12j_nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hammer" {...props}></Icon>
