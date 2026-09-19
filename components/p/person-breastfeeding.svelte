<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at31ysbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="at31ysbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-breastfeeding" {...props}></Icon>
