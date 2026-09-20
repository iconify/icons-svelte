<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-c1zgbnj.css';
import '../../css/a/amusoxbhb.css';
import '../../css/s/serii-led.css';
import '../../css/c/cuarf-7ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i-c1zgbnj"/><path class="amusoxbhb"/><path class="serii-led"/><path class="cuarf-7ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:collision" {...props}></Icon>
