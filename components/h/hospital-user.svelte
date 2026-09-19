<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb6b2vb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bb6b2vb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hospital-user" {...props}></Icon>
