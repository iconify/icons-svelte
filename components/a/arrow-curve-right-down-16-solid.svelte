<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgbl1b5my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cgbl1b5my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-right-down-16-solid" {...props}></Icon>
