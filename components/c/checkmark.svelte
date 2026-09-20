<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_3phbckt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w_3phbckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:checkmark" {...props}></Icon>
