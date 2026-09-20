<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku34nyb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku34nyb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-left-line" {...props}></Icon>
