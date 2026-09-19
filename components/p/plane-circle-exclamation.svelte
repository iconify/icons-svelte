<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-681ibkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m-681ibkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plane-circle-exclamation" {...props}></Icon>
