<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj4jtmo4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wj4jtmo4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:nutritionix" {...props}></Icon>
