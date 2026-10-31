<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc_wdvbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_wdvbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radar-round" {...props}></Icon>
