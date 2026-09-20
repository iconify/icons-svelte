<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo9-u_9hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mo9-u_9hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:broom" {...props}></Icon>
