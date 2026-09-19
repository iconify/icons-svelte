<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsmsj-9cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nsmsj-9cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:heart-filled" {...props}></Icon>
