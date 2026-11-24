<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obe9jcnoy.css';
import '../../css/x/xnw8m44ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obe9jcnoy"/><path class="xnw8m44ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:captions-off-filled" {...props}></Icon>
