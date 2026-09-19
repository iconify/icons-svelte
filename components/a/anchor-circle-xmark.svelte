<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp6rlcbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xp6rlcbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:anchor-circle-xmark" {...props}></Icon>
