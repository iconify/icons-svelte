<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw0pzeiyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uw0pzeiyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hiv-self-test" {...props}></Icon>
