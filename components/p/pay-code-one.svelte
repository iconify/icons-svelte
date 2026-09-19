<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/w/w812kkozp.css';
import '../../css/d/d1ny5kbfu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUV14vb0V"><g class="aql7dnt-u"><path class="w812kkozp"/><path class="d1ny5kbfu"/></g></mask></defs><path mask="url(#SVGUV14vb0V)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pay-code-one" {...props}></Icon>
