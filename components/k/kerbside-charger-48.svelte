<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_jk-9bgq.css';
import '../../css/m/mr762oh0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k_jk-9bgq"/><path class="mr762oh0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kerbside-charger-48" {...props}></Icon>
