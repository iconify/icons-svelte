<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h974lpb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h974lpb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:edit-pencil" {...props}></Icon>
