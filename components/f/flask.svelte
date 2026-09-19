<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up69kityd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="up69kityd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:flask" {...props}></Icon>
