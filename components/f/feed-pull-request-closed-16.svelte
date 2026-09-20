<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxiz10l3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bxiz10l3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-pull-request-closed-16" {...props}></Icon>
