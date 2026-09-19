<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys5e_r7yr.css';
import '../../css/e/ey1v8gbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":12};
const content = `<path class="ys5e_r7yr"/><path class="ey1v8gbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:fastforward" {...props}></Icon>
