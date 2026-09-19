<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzbs20ffj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mzbs20ffj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:player-me" {...props}></Icon>
