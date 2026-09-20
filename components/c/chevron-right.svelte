<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk5u3zgrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wk5u3zgrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:chevron-right" {...props}></Icon>
