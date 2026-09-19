<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umcihdb7e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJKBlpclM"><path class="umcihdb7e"/></mask></defs><path mask="url(#SVGJKBlpclM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-top-two" {...props}></Icon>
