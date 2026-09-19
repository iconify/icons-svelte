<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge3_ow_4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ge3_ow_4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-drop" {...props}></Icon>
