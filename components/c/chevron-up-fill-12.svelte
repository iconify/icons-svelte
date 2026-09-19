<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z93e_zjvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z93e_zjvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-up-fill-12" {...props}></Icon>
