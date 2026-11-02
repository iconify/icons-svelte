<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/til_8xb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="til_8xb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-down-16-solid" {...props}></Icon>
