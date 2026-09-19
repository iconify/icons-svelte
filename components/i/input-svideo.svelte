<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvjg4ul6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="bvjg4ul6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:input-svideo" {...props}></Icon>
