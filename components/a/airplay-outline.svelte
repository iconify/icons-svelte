<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrvn70_6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mrvn70_6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:airplay-outline" {...props}></Icon>
