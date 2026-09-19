<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz1736cer.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG68bY5cqX"><ellipse class="wz1736cer"/></mask></defs><path mask="url(#SVG68bY5cqX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:oval-one" {...props}></Icon>
