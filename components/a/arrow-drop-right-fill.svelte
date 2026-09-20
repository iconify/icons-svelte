<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eck_ywbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eck_ywbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-right-fill" {...props}></Icon>
