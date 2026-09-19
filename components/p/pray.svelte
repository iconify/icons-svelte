<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1_nxgx4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="v1_nxgx4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pray" {...props}></Icon>
