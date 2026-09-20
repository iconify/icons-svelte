<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8jx4vivo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f8jx4vivo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pin-fill-16" {...props}></Icon>
