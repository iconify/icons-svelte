<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj1ir7biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1ir7biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-cross" {...props}></Icon>
