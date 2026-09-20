<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_ynsmfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ke_ynsmfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:layer-group-solid" {...props}></Icon>
