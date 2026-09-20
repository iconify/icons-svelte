<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gef84bcbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gef84bcbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:box" {...props}></Icon>
