<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su9dknbed.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p4fy0sbhc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/b/bgg_hqo-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGKxcyRbQG" class="su9dknbed"/></defs><g class="ft5dv1b6b"><path class="p4fy0sbhc"/><use href="#SVGKxcyRbQG" class="mc2zb0bvp"/><use href="#SVGKxcyRbQG"/><path class="bgg_hqo-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:file-export-duotone" {...props}></Icon>
