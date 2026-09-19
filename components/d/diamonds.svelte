<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/v/v8rhqlbnk.css';
import '../../css/d/d-51ep7ot.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTPGcnepP"><g class="aql7dnt-u"><path class="v8rhqlbnk"/><path class="d-51ep7ot"/></g></mask></defs><path mask="url(#SVGTPGcnepP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:diamonds" {...props}></Icon>
