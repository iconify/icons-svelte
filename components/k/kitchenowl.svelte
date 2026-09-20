<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf24crklk.css';
import '../../css/y/yr2jp-bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bf24crklk"/><path class="yr2jp-bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitchenowl" {...props}></Icon>
