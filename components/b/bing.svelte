<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqw534qdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sqw534qdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bing" {...props}></Icon>
