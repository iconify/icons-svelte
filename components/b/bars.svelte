<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkeyf6b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bkeyf6b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bars" {...props}></Icon>
