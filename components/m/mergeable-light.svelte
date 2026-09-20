<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z00yxpbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z00yxpbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mergeable-light" {...props}></Icon>
