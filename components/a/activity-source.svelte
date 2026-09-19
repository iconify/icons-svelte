<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig6wfsbtl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLlepUcCE"><path class="ig6wfsbtl"/></mask></defs><path mask="url(#SVGLlepUcCE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:activity-source" {...props}></Icon>
