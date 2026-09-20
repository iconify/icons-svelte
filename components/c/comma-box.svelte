<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svl-a4biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svl-a4biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comma-box" {...props}></Icon>
