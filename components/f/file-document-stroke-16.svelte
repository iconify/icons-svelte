<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaht5yaep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qaht5yaep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-document-stroke-16" {...props}></Icon>
