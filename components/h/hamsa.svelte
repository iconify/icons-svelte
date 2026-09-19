<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ht3dbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_ht3dbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hamsa" {...props}></Icon>
