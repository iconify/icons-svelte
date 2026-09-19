<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxf4d6pbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxf4d6pbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-down-02" {...props}></Icon>
