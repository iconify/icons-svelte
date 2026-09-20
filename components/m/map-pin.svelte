<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4x-fs84m.css';
import '../../css/u/uk7qgtbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4x-fs84m"/><circle class="uk7qgtbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:map-pin" {...props}></Icon>
