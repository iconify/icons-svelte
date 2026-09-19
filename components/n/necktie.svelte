<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l301i3_fe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8jIuhdOj"><path class="l301i3_fe"/></mask></defs><path mask="url(#SVG8jIuhdOj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:necktie" {...props}></Icon>
