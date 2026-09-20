<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_l-v3ilc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l-v3ilc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:plug-2-line" {...props}></Icon>
