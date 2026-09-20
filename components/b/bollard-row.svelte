<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd87fv_an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rd87fv_an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bollard-row" {...props}></Icon>
