<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vmh3nbbvo.css';
import '../../css/a/anh5kmhkf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcNm2IbVG"><g class="ft5dv1b6b"><path class="vmh3nbbvo"/><path class="anh5kmhkf"/></g></mask></defs><path mask="url(#SVGcNm2IbVG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:road-cone" {...props}></Icon>
