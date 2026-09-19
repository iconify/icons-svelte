<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3q0eviez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3q0eviez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:compass" {...props}></Icon>
