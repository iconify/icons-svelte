<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oro-z9kun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oro-z9kun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docmost-light" {...props}></Icon>
