<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/b/bg4nr-b2f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqZE6mclN"><g class="ft5dv1b6b"><path class="arj7difgh"/><path clip-rule="evenodd" class="bg4nr-b2f"/></g></mask></defs><path mask="url(#SVGqZE6mclN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:more-three" {...props}></Icon>
