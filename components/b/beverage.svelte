<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj4omabni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vj4omabni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:beverage" {...props}></Icon>
