<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf5r4xb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kf5r4xb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moon-stroke-20" {...props}></Icon>
