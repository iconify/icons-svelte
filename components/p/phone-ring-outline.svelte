<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpoa-6mah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpoa-6mah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-ring-outline" {...props}></Icon>
