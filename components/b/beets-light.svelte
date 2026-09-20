<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt6-z2b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt6-z2b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-light" {...props}></Icon>
