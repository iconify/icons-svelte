<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr_sv_boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lr_sv_boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-outline-with-star" {...props}></Icon>
