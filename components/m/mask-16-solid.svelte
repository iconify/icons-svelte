<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf1mcybca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cf1mcybca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:mask-16-solid" {...props}></Icon>
