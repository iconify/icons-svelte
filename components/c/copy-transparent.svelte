<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j66vk4b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j66vk4b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:copy-transparent" {...props}></Icon>
