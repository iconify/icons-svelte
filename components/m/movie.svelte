<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tvgauyb5v.css';
import '../../css/b/b77-k2blg.css';
import '../../css/q/qczrjccey.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzfmErcyW"><g class="s9cl3zbei"><path class="tvgauyb5v"/><path class="b77-k2blg"/><path class="qczrjccey"/></g></mask></defs><path mask="url(#SVGzfmErcyW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:movie" {...props}></Icon>
