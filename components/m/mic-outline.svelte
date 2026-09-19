<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh6ex02dp.css';
import '../../css/o/opkm_bb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mh6ex02dp"/><path class="opkm_bb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-outline" {...props}></Icon>
