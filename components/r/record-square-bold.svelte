<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_csnkffw.css';
import '../../css/k/kvt6enbri.css';
import '../../css/q/qwhmxvbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_csnkffw"/><path class="kvt6enbri"/><path clip-rule="evenodd" class="qwhmxvbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-square-bold" {...props}></Icon>
