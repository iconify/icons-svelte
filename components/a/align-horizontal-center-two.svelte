<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khyr1cc7b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZ1FsecDt"><path class="khyr1cc7b"/></mask></defs><path mask="url(#SVGZ1FsecDt)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-horizontal-center-two" {...props}></Icon>
