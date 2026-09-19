<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deq4hgrol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="deq4hgrol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:play-pause-16-solid" {...props}></Icon>
