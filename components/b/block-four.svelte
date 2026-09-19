<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o52m7dbbd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgUj2T2pb"><path class="o52m7dbbd"/></mask></defs><path mask="url(#SVGgUj2T2pb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-four" {...props}></Icon>
