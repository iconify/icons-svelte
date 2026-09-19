<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwc03jzoe.css';
import '../../css/z/zalphcmjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwc03jzoe"/><path class="zalphcmjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:progress-bar" {...props}></Icon>
