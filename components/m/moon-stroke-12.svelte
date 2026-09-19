<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpsk3tlwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dpsk3tlwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moon-stroke-12" {...props}></Icon>
