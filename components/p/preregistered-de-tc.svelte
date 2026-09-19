<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-fh7-g-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-fh7-g-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-de-tc" {...props}></Icon>
