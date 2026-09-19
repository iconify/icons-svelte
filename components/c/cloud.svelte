<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhhvm1c5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="vhhvm1c5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:cloud" {...props}></Icon>
