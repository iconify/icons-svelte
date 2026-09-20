<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6vvru-gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j6vvru-gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-right-left-20-solid" {...props}></Icon>
