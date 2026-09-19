<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do1xd6lny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="do1xd6lny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-left-fill-12" {...props}></Icon>
