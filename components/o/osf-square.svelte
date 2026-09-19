<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieh18j3cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ieh18j3cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:osf-square" {...props}></Icon>
