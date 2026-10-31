<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swjdv_bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swjdv_bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dollar-sign-gloss" {...props}></Icon>
