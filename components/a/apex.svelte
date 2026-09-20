<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz58fnbwx.css';
import '../../css/x/x4shk053m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz58fnbwx"/><path class="x4shk053m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:apex" {...props}></Icon>
