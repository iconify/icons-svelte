<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjt7edbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjt7edbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-search-outline" {...props}></Icon>
