<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljpp4jbkd.css';
import '../../css/j/jmkpn4wvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ljpp4jbkd"/><path class="jmkpn4wvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-flare-20" {...props}></Icon>
