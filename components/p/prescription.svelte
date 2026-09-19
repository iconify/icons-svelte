<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnfh_24gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pnfh_24gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:prescription" {...props}></Icon>
