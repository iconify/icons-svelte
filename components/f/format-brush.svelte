<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qdzwi4b4l.css';
import '../../css/v/vaa0ik_1j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPm4kxc4w"><g class="v3_i3wktz"><path class="qdzwi4b4l"/><path class="vaa0ik_1j"/></g></mask></defs><path mask="url(#SVGPm4kxc4w)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:format-brush" {...props}></Icon>
