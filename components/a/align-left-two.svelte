<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4qqmmb7p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9ZpiTHEA"><path class="r4qqmmb7p"/></mask></defs><path mask="url(#SVG9ZpiTHEA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-left-two" {...props}></Icon>
