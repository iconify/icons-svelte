<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0ri7lbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e0ri7lbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-right-16-solid" {...props}></Icon>
