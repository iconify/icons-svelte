<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue2su8odp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ue2su8odp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bell" {...props}></Icon>
