<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjjfd2g-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jjjfd2g-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-markings-dashes" {...props}></Icon>
