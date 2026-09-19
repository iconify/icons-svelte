<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmjht8bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wmjht8bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-right-16-solid" {...props}></Icon>
