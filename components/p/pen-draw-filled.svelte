<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb5j8cb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb5j8cb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-draw-filled" {...props}></Icon>
