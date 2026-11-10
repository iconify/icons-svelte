<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2oi3ccis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e2oi3ccis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-arrow-path-16-solid" {...props}></Icon>
