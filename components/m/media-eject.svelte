<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csdw9chgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csdw9chgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-eject" {...props}></Icon>
