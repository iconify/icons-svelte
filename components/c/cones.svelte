<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/t/txhjy5bum.css';
import '../../css/j/j7b_4jb0s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDZvEddeV"><g class="ufeehvblu"><path class="txhjy5bum"/><path class="j7b_4jb0s"/></g></mask></defs><path mask="url(#SVGDZvEddeV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:cones" {...props}></Icon>
