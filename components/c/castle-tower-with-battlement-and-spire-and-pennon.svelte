<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzt1dacmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jzt1dacmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-tower-with-battlement-and-spire-and-pennon" {...props}></Icon>
