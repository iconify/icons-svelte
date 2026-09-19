<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi7vgif3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yi7vgif3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basketball-stroke-16" {...props}></Icon>
