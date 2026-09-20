<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bp4w13bxo.css';
import '../../css/x/xzysizizn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bp4w13bxo"/><path class="xzysizizn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:build" {...props}></Icon>
