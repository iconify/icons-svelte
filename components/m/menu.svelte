<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9_ictxqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d9_ictxqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:menu" {...props}></Icon>
