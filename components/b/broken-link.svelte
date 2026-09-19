<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hphbwmrgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":496};
const content = `<path class="hphbwmrgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:broken-link" {...props}></Icon>
