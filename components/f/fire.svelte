<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/parj51b-v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9H2JBOPY"><path class="parj51b-v"/></mask></defs><path mask="url(#SVG9H2JBOPY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:fire" {...props}></Icon>
