<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--o8dbgk.css';
import '../../css/y/yol252b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="v--o8dbgk"/><path class="yol252b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:position-o" {...props}></Icon>
