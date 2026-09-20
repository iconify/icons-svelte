<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9n4vlb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i9n4vlb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bee" {...props}></Icon>
