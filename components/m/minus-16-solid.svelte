<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8h6fkdvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p8h6fkdvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus-16-solid" {...props}></Icon>
