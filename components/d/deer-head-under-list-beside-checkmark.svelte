<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr5hwuboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nr5hwuboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:deer-head-under-list-beside-checkmark" {...props}></Icon>
