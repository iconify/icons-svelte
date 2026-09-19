<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8a8frnyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8a8frnyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:opentype" {...props}></Icon>
