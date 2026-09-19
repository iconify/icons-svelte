<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6_x99d5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":448};
const content = `<path class="t6_x99d5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hand-pointer-right" {...props}></Icon>
