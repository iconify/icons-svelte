<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj_svym1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rj_svym1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-cursor-1-solid" {...props}></Icon>
