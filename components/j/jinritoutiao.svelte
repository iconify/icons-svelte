<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbw7r3bce.css';
import '../../css/t/tcu8_9yus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xbw7r3bce"/><path clip-rule="evenodd" class="tcu8_9yus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jinritoutiao" {...props}></Icon>
