<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8sq58bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j8sq58bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:horse-solid" {...props}></Icon>
