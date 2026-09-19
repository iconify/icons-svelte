<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/b/bp02gi_2r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGySYQzboH"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="bp02gi_2r"/></g></mask></defs><path mask="url(#SVGySYQzboH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:down-square" {...props}></Icon>
