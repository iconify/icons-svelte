<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_4g82bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_4g82bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-mask-outline" {...props}></Icon>
