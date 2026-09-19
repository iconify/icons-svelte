<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-g0x1_9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-g0x1_9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-add-outline" {...props}></Icon>
