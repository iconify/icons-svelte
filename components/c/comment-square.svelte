<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr0lfd5rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sr0lfd5rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:comment-square" {...props}></Icon>
