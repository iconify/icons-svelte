<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8jm71bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8jm71bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-minus-fill" {...props}></Icon>
