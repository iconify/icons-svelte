<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esp1oilti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="esp1oilti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:descent" {...props}></Icon>
