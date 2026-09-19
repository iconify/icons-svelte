<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipgh2pb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ipgh2pb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:car-alt" {...props}></Icon>
