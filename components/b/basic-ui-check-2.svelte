<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buhyrjbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="buhyrjbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-check-2" {...props}></Icon>
