<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9ejojb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t9ejojb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nine-point-star-outline" {...props}></Icon>
