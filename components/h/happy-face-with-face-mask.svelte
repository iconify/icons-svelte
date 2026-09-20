<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4b69pz9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n4b69pz9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:happy-face-with-face-mask" {...props}></Icon>
