<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzy1_7bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mzy1_7bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:menu-fill-12" {...props}></Icon>
