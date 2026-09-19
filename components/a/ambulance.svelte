<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcwzkjb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tcwzkjb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ambulance" {...props}></Icon>
