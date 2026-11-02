<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-1lzjfhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-1lzjfhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-left-16-solid" {...props}></Icon>
