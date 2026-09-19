<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oke-pbcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="oke-pbcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-inner" {...props}></Icon>
