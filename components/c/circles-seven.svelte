<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktrttabkl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGN8D5Ad5C"><path clip-rule="evenodd" class="ktrttabkl"/></mask></defs><path mask="url(#SVGN8D5Ad5C)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:circles-seven" {...props}></Icon>
