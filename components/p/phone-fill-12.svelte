<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxbikpuly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uxbikpuly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-fill-12" {...props}></Icon>
