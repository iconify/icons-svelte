<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy2o1zb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jy2o1zb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:crosshairs" {...props}></Icon>
