<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m44awd2kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m44awd2kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:appstore-o" {...props}></Icon>
