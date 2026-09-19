<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f34p5dbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f34p5dbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-happy" {...props}></Icon>
