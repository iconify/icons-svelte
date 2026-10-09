<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7-jacac.css';
import '../../css/r/rmei1lbaz.css';
import '../../css/t/txgfsobga.css';
import '../../css/v/vqtn4ybkd.css';
import '../../css/a/a97kokbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mp7-jacac"/><path class="rmei1lbaz"/><path class="txgfsobga"/><path class="vqtn4ybkd"/><path class="a97kokbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helicopter-48" {...props}></Icon>
