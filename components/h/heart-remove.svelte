<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbm4hfb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbm4hfb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart-remove" {...props}></Icon>
