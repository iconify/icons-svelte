<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kma8rmbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kma8rmbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image" {...props}></Icon>
