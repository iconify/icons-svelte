<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj--fcbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uj--fcbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-under-taxi-checkerboard" {...props}></Icon>
