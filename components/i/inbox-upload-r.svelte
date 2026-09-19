<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/o/oil91sbfz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVHe5TosT"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="oil91sbfz"/></g></mask></defs><path mask="url(#SVGVHe5TosT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:inbox-upload-r" {...props}></Icon>
