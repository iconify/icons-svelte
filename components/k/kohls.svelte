<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onikkmh6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onikkmh6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kohls" {...props}></Icon>
