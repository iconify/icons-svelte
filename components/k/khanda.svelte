<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwks0ac9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwks0ac9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:khanda" {...props}></Icon>
