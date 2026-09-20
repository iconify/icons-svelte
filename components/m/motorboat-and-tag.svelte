<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saq33obio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="saq33obio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-tag" {...props}></Icon>
