<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2s84ct4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2s84ct4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alpinedotjs" {...props}></Icon>
