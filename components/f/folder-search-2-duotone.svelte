<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x7-tn3b9i.css';
import '../../css/r/rnefhfbia.css';
import '../../css/l/lpbjfab7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x7-tn3b9i"/><path class="rnefhfbia"/><path class="lpbjfab7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-search-2-duotone" {...props}></Icon>
