<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-fh4lbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="u-fh4lbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-point-up" {...props}></Icon>
