<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_r13u14c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_r13u14c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ceur" {...props}></Icon>
