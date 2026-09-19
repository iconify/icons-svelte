<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzeot8bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vzeot8bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cpanel-wordmark" {...props}></Icon>
