<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7mgyobwh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVVTypbHn"><path class="f7mgyobwh"/></mask></defs><path mask="url(#SVGVVTypbHn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:play-one" {...props}></Icon>
