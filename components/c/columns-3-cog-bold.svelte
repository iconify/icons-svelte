<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3lwmsbeo.css';
import '../../css/w/w17zy0bco.css';
import '../../css/d/dan73zqnv.css';
import '../../css/s/shroyfbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3lwmsbeo"/><path clip-rule="evenodd" class="w17zy0bco"/><path class="dan73zqnv"/><path class="shroyfbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-cog-bold" {...props}></Icon>
