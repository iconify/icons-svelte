<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g72wj7u_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g72wj7u_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:briefcase" {...props}></Icon>
