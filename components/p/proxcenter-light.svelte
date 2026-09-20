<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov7c-h-ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ov7c-h-ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxcenter-light" {...props}></Icon>
