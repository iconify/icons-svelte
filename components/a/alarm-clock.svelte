<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nfpxpmyht.css';
import '../../css/q/ql9sd2bvf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1aXMSbnJ"><g class="v3_i3wktz"><path class="nfpxpmyht"/><path class="ql9sd2bvf"/></g></mask></defs><path mask="url(#SVG1aXMSbnJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:alarm-clock" {...props}></Icon>
