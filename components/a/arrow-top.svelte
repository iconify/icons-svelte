<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vji3-_bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vji3-_bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-top" {...props}></Icon>
