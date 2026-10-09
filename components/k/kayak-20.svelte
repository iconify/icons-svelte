<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx6i4llwi.css';
import '../../css/w/woo7zdu1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mx6i4llwi"/><path class="woo7zdu1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kayak-20" {...props}></Icon>
