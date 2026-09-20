<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo2-g_b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path clip-rule="evenodd" class="oo2-g_b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:play-store-alt" {...props}></Icon>
