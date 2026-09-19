<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_--k2e7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u_--k2e7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bible" {...props}></Icon>
