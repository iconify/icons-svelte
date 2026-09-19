<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfam4-egf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bfam4-egf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circletwitter" {...props}></Icon>
