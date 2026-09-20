<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br7nqpp0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="br7nqpp0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn-beside-trail-blazes-up" {...props}></Icon>
