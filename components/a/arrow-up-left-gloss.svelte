<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyhqnccsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyhqnccsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-left-gloss" {...props}></Icon>
