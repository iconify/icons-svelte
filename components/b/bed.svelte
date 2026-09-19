<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ges_c3t5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ges_c3t5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:bed" {...props}></Icon>
