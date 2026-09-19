<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7ceab4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dy7ceab4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-slash-20-solid" {...props}></Icon>
