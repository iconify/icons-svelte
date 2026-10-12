<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4bzp0bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4bzp0bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-stroke-20" {...props}></Icon>
