<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/geju8gabu.css';
import '../../css/q/qz7nj6phs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAfVvubCX"><g class="aql7dnt-u"><path class="geju8gabu"/><path class="qz7nj6phs"/></g></mask></defs><path mask="url(#SVGAfVvubCX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:round-mask" {...props}></Icon>
