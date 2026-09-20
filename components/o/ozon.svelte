<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtnow_b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":485,"height":106};
const content = `<path class="qtnow_b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ozon" {...props}></Icon>
