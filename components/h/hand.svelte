<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi870p-xs.css';
import '../../css/f/fcxs7zbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vi870p-xs"/><path class="fcxs7zbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hand" {...props}></Icon>
