<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z06xlpj0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="z06xlpj0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-up" {...props}></Icon>
