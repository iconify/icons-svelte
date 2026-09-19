<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/oyq5l32hv.css';
import '../../css/s/skzye-b9q.css';
import '../../css/d/dx2uoqbap.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNF40UdJU"><g class="v3_i3wktz"><path class="oyq5l32hv"/><path class="skzye-b9q"/><path class="dx2uoqbap"/></g></mask></defs><path mask="url(#SVGNF40UdJU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:download-laptop" {...props}></Icon>
