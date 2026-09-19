<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bthd_yb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bthd_yb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-20-solid" {...props}></Icon>
