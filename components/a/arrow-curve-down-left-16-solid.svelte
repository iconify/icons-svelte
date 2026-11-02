<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-5n0kbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y-5n0kbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-left-16-solid" {...props}></Icon>
