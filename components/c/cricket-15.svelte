<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az__ulu8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="az__ulu8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cricket-15" {...props}></Icon>
