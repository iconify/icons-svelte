<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkl81gx0s.css';
import '../../css/e/eevvws5ct.css';
import '../../css/h/hol_21ctj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="nkl81gx0s"/><path class="eevvws5ct"/><path class="hol_21ctj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidarr" {...props}></Icon>
