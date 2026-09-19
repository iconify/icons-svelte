<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/w/w-3mi7j8w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWFiNMeUh"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="w-3mi7j8w"/></g></mask></defs><path mask="url(#SVGWFiNMeUh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:layout-two" {...props}></Icon>
