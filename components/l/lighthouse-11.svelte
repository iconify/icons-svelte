<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyuod_fzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="uyuod_fzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:lighthouse-11" {...props}></Icon>
