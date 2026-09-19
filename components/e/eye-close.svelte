<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2nq22b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m2nq22b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:eye-close" {...props}></Icon>
