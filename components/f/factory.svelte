<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5dskybkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g5dskybkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:factory" {...props}></Icon>
