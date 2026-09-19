<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/a/aheys2bnt.css';
import '../../css/h/hvfyshbwi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdTSSBenS"><g class="gopnm44um"><path class="aheys2bnt"/><path class="hvfyshbwi"/></g></mask></defs><path mask="url(#SVGdTSSBenS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:flash-payment" {...props}></Icon>
