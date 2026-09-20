<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xota8vqjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xota8vqjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-notifications" {...props}></Icon>
