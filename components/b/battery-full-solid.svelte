<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_j7lbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="my_j7lbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:battery-full-solid" {...props}></Icon>
