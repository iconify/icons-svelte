<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k-xlr_blp.css';
import '../../css/s/su9dknbed.css';
import '../../css/b/bgg_hqo-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k-xlr_blp"/><path class="su9dknbed"/><path class="bgg_hqo-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:file-export" {...props}></Icon>
