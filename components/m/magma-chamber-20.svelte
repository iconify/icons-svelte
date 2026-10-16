<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0topkbwv.css';
import '../../css/w/w673-_bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j0topkbwv"/><path class="w673-_bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magma-chamber-20" {...props}></Icon>
