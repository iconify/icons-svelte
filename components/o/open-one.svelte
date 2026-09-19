<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mf4kxbb7i.css';
import '../../css/q/qp5l2y6-o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzIoW9KLC"><g class="aql7dnt-u"><path class="mf4kxbb7i"/><circle class="qp5l2y6-o"/></g></mask></defs><path mask="url(#SVGzIoW9KLC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:open-one" {...props}></Icon>
