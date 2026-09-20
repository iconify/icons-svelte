<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn4bs8axk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="bn4bs8axk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waxing-gibbous-1" {...props}></Icon>
