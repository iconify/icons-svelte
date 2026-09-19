<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu2vv7b8r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmIvModQC"><path class="lu2vv7b8r"/></mask></defs><path mask="url(#SVGmIvModQC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:easy" {...props}></Icon>
