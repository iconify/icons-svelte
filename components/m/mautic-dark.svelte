<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3ls2vrqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3ls2vrqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mautic-dark" {...props}></Icon>
