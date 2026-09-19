<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4b1xmw_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j4b1xmw_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:no-symbol" {...props}></Icon>
