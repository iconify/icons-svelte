<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv1pozbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xv1pozbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:anti-clockwise-outline" {...props}></Icon>
