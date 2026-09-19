<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdwwqyb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pdwwqyb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:image" {...props}></Icon>
