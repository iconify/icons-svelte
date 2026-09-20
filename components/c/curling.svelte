<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw7q4hb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vw7q4hb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:curling" {...props}></Icon>
