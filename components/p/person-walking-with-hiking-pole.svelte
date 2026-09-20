<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-a68sb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g-a68sb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-hiking-pole" {...props}></Icon>
