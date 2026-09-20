<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idihgbbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idihgbbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-clock-outline" {...props}></Icon>
