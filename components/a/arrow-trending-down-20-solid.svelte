<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8jj3acng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i8jj3acng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-trending-down-20-solid" {...props}></Icon>
