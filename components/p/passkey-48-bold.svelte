<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t55dglbwd.css';
import '../../css/i/i2dsa1fpp.css';
import '../../css/m/mpef91b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t55dglbwd"/><path class="i2dsa1fpp"/><path class="mpef91b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:passkey-48-bold" {...props}></Icon>
