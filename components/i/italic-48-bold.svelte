<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r29txbtvf.css';
import '../../css/w/wif1j2bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r29txbtvf"/><path class="wif1j2bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:italic-48-bold" {...props}></Icon>
