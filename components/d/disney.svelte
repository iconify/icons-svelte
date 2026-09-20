<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9drcb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":294.423};
const content = `<path class="kd9drcb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:disney" {...props}></Icon>
