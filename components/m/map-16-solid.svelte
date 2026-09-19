<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfudi9b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yfudi9b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:map-16-solid" {...props}></Icon>
