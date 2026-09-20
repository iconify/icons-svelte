<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxhz30baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oxhz30baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:factory" {...props}></Icon>
