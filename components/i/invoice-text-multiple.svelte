<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmdhz5s5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdhz5s5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-multiple" {...props}></Icon>
