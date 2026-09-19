<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehk72fbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ehk72fbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path-rounded-square-16-solid" {...props}></Icon>
