<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbs6tsbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cbs6tsbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face3-small" {...props}></Icon>
