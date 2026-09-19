<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9y_fntnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="b9y_fntnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:amazon" {...props}></Icon>
