<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stn_egbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="stn_egbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:module-solid" {...props}></Icon>
