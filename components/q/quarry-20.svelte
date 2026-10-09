<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcn2ntbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tcn2ntbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quarry-20" {...props}></Icon>
