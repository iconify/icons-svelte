<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5c26tbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5c26tbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder" {...props}></Icon>
