<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jsspaw5ps.css';
import '../../css/e/e6j8h5b3s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgpjYybXi"><g class="v3_i3wktz"><path class="jsspaw5ps"/><path class="e6j8h5b3s"/></g></mask></defs><path mask="url(#SVGgpjYybXi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:clipboard" {...props}></Icon>
