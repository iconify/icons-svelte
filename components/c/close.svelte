<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_q3o-bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="h_q3o-bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:close" {...props}></Icon>
