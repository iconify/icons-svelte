<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccz98ti9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ccz98ti9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:road-barrier" {...props}></Icon>
