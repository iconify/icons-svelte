<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq1twmhyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qq1twmhyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-down-16-solid" {...props}></Icon>
