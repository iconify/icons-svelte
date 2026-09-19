<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svjkzmbvm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDCDRabPH"><path class="svjkzmbvm"/></mask></defs><path mask="url(#SVGDCDRabPH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:navigation" {...props}></Icon>
