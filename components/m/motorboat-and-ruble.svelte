<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtqgm_p1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mtqgm_p1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-ruble" {...props}></Icon>
