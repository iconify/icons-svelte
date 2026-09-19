<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3xlkio1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3xlkio1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-heart" {...props}></Icon>
