<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q9z220ulp.css';
import '../../css/b/b98o3ib5q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlcr4TdQJ"><g class="v3_i3wktz"><path class="q9z220ulp"/><path class="b98o3ib5q"/></g></mask></defs><path mask="url(#SVGlcr4TdQJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:paper-ship" {...props}></Icon>
