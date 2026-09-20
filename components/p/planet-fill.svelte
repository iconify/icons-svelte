<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lycqc1r5r.css';
import '../../css/z/zphee1bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lycqc1r5r"/><path class="zphee1bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:planet-fill" {...props}></Icon>
