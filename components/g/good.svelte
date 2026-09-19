<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs3tzmb_z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGD7akPb4b"><path class="fs3tzmb_z"/></mask></defs><path mask="url(#SVGD7akPb4b)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:good" {...props}></Icon>
