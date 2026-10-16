<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8w6o6bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w8w6o6bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moonset-20-bold" {...props}></Icon>
