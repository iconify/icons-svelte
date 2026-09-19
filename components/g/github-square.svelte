<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggysgtp2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ggysgtp2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:github-square" {...props}></Icon>
