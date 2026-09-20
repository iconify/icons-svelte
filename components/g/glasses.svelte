<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9o9xvyop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9o9xvyop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:glasses" {...props}></Icon>
