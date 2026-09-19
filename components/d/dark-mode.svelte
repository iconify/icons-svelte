<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blyiy0b4o.css';
import '../../css/l/lu-nqrbmy.css';
import '../../css/t/tmatxnbbk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHlsFAdQb"><g class="blyiy0b4o"><path class="lu-nqrbmy"/><path class="tmatxnbbk"/></g></mask></defs><path mask="url(#SVGHlsFAdQb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:dark-mode" {...props}></Icon>
