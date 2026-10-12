<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs_dfacjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hs_dfacjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-fill-20" {...props}></Icon>
