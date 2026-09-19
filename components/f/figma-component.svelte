<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98f580tp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGc84LZbFk"><path class="k98f580tp"/></mask></defs><path mask="url(#SVGc84LZbFk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:figma-component" {...props}></Icon>
