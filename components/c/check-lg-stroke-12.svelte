<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb0t6_b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cb0t6_b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-lg-stroke-12" {...props}></Icon>
