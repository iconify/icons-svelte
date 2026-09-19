<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9sb41obi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="s9sb41obi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:group" {...props}></Icon>
