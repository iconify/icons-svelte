<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bguqskafl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bguqskafl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:electrical-switch-and-bolt" {...props}></Icon>
