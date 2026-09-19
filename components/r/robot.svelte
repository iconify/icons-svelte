<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7olm2c0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="w7olm2c0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:robot" {...props}></Icon>
