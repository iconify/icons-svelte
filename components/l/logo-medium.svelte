<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-6li450q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-6li450q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-medium" {...props}></Icon>
