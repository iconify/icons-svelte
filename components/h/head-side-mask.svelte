<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8he06wsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8he06wsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:head-side-mask" {...props}></Icon>
