<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwqp5qbdv.css';
import '../../css/w/wi3s5ubtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jwqp5qbdv"/><path class="wi3s5ubtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hospital" {...props}></Icon>
