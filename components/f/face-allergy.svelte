<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xorx1caxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="xorx1caxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:face-allergy" {...props}></Icon>
