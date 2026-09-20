<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy6fc6btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wy6fc6btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:desktop-download" {...props}></Icon>
