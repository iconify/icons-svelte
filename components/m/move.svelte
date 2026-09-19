<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/l44v9bgvv.css';
import '../../css/c/c4ntg5ecs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJAkoWcDZ"><g class="aql7dnt-u"><path class="l44v9bgvv"/><path class="c4ntg5ecs"/></g></mask></defs><path mask="url(#SVGJAkoWcDZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:move" {...props}></Icon>
