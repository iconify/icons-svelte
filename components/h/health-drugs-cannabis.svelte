<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7xpljjum.css';
import '../../css/w/wsh9lzbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m7xpljjum"/><path class="wsh9lzbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-drugs-cannabis" {...props}></Icon>
