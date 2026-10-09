<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shozmhblo.css';
import '../../css/e/ex4r6bbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="shozmhblo"/><path class="ex4r6bbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fusion-20-bold" {...props}></Icon>
