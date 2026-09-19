<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-5av7bmy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGt9zVddCE"><path clip-rule="evenodd" class="j-5av7bmy"/></mask></defs><path mask="url(#SVGt9zVddCE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:back" {...props}></Icon>
