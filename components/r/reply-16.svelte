<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjn9f7o-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gjn9f7o-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:reply-16" {...props}></Icon>
