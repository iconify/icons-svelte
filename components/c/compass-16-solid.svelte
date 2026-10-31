<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8id8bbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y8id8bbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass-16-solid" {...props}></Icon>
