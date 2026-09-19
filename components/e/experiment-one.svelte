<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xzkp8w4-s.css';
import '../../css/q/qc6zml-vw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr1BG7bpF"><g class="v3_i3wktz"><path class="xzkp8w4-s"/><path class="qc6zml-vw"/></g></mask></defs><path mask="url(#SVGr1BG7bpF)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:experiment-one" {...props}></Icon>
