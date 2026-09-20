<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo2aflbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xo2aflbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-right-12" {...props}></Icon>
