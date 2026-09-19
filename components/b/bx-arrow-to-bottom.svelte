<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul1wxcbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul1wxcbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arrow-to-bottom" {...props}></Icon>
