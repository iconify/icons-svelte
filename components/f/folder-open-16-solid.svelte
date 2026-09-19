<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6vko2bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w6vko2bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-open-16-solid" {...props}></Icon>
