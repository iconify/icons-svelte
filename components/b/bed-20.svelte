<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_jeenba.css';
import '../../css/k/k0o87zohe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jm_jeenba"/><path class="k0o87zohe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-20" {...props}></Icon>
