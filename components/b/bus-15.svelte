<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z504-5p1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z504-5p1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bus-15" {...props}></Icon>
