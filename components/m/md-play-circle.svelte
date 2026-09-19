<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ombmqu5rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ombmqu5rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-play-circle" {...props}></Icon>
