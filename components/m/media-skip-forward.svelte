<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu77ymb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uu77ymb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-skip-forward" {...props}></Icon>
