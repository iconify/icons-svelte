<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c75q14plq.css';
import '../../css/r/r2erxnb7t.css';
import '../../css/a/ao_2tkpff.css';
import '../../css/a/av160dcvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c75q14plq"/><path class="r2erxnb7t"/><path class="ao_2tkpff"/><path class="av160dcvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:battery-charging-outline" {...props}></Icon>
