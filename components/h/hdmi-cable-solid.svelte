<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l277xdb4x.css';
import '../../css/x/xqkddkb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l277xdb4x"/><path class="xqkddkb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hdmi-cable-solid" {...props}></Icon>
