<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r0ng9--ek.css';
import '../../css/z/zfyrcjb-q.css';
import '../../css/z/zhssuvbwg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBYcKnVME"><g class="ufeehvblu"><path class="r0ng9--ek"/><path clip-rule="evenodd" class="zfyrcjb-q"/><path class="zhssuvbwg"/></g></mask></defs><path mask="url(#SVGBYcKnVME)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bookmark" {...props}></Icon>
