<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8nup8brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y8nup8brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-dots" {...props}></Icon>
