<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q239t9bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="q239t9bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bookmark" {...props}></Icon>
