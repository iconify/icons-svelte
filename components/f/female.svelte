<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-mk3b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":432};
const content = `<path class="wk-mk3b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:female" {...props}></Icon>
