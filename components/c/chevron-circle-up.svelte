<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq4yvfb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="yq4yvfb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-circle-up" {...props}></Icon>
