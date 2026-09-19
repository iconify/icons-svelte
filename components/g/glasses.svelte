<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/o4fdh1b1f.css';
import '../../css/h/h05jvmbea.css';
import '../../css/i/il6_1tbws.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGStGRUdQJ"><g class="aql7dnt-u"><circle class="o4fdh1b1f"/><circle class="h05jvmbea"/><path class="il6_1tbws"/></g></mask></defs><path mask="url(#SVGStGRUdQJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:glasses" {...props}></Icon>
