<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p142kmbwe.css';
import '../../css/x/xo3mlcr-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p142kmbwe"/><path class="xo3mlcr-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-browsers" {...props}></Icon>
