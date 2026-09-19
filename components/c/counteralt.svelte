<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7i3mcv0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="p7i3mcv0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:counteralt" {...props}></Icon>
