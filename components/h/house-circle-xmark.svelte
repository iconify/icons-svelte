<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdrsvybiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xdrsvybiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-circle-xmark" {...props}></Icon>
