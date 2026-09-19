<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/a/aq7j5jb9a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOLB8NbQT"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="aq7j5jb9a"/></g></mask></defs><path mask="url(#SVGOLB8NbQT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:left-bar" {...props}></Icon>
