<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkn4d7nbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xkn4d7nbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:expand" {...props}></Icon>
