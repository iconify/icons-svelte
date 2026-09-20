<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc9q056bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tc9q056bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:michigan-upper-peninsula" {...props}></Icon>
