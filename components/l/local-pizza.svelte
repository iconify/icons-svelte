<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuzej1iwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="xuzej1iwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-pizza" {...props}></Icon>
