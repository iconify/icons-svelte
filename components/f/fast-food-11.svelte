<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8fejlbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="n8fejlbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fast-food-11" {...props}></Icon>
