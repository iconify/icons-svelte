<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvfdsibyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yvfdsibyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-16-solid" {...props}></Icon>
