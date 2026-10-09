<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af023dsnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="af023dsnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-snow-20" {...props}></Icon>
