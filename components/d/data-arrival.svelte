<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/o3eo20bpg.css';
import '../../css/j/jgkv41b5o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJ1qr9dfU"><g class="v3_i3wktz"><path clip-rule="evenodd" class="o3eo20bpg"/><path class="jgkv41b5o"/></g></mask></defs><path mask="url(#SVGJ1qr9dfU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:data-arrival" {...props}></Icon>
