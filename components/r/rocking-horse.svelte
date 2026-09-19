<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/iv837lbrb.css';
import '../../css/x/xx_r_sbcu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIj1pjezi"><g class="aql7dnt-u"><path class="iv837lbrb"/><path class="xx_r_sbcu"/></g></mask></defs><path mask="url(#SVGIj1pjezi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rocking-horse" {...props}></Icon>
