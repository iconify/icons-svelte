<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_8qphb1a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCOhucbsT"><path class="n_8qphb1a"/></mask></defs><path mask="url(#SVGCOhucbsT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:quadrilateral" {...props}></Icon>
