<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxpu4qbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxpu4qbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:paper-plane" {...props}></Icon>
