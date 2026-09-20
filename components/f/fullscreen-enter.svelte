<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_oaqpieo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i_oaqpieo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:fullscreen-enter" {...props}></Icon>
