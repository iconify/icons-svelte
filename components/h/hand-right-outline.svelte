<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grhtrnaya.css';
import '../../css/o/ohiekfb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grhtrnaya"/><path class="ohiekfb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hand-right-outline" {...props}></Icon>
