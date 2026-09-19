<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2-13jbdu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGJR8obeK"><path class="o2-13jbdu"/></mask></defs><path mask="url(#SVGGJR8obeK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:five" {...props}></Icon>
