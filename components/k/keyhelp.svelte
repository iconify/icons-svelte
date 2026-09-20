<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgxha5b3d.css';
import '../../css/x/xgliqgswb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgxha5b3d"/><path class="xgliqgswb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keyhelp" {...props}></Icon>
