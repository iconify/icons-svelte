<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3j068ntp.css';
import '../../css/u/uwilteebl.css';
import '../../css/j/jeboob2cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y3j068ntp"/><path class="uwilteebl"/><path class="jeboob2cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-incoming-48" {...props}></Icon>
