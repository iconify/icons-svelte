<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0k1bibib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z0k1bibib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fishes" {...props}></Icon>
