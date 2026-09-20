<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8dx0dv6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b8dx0dv6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:analog-tv-with-rabbitears" {...props}></Icon>
