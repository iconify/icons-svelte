<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpj_gzx8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="gpj_gzx8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:picture-in-picture" {...props}></Icon>
