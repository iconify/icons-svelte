<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atomtfbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="atomtfbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-circle-16-solid" {...props}></Icon>
