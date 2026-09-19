<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9ga5g8gl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7t90jevq"><path class="f9ga5g8gl"/></mask></defs><path mask="url(#SVG7t90jevq)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rectangle" {...props}></Icon>
