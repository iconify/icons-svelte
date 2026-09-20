<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7l6k569g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u7l6k569g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-baht" {...props}></Icon>
