<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12ji_bzg.css';
import '../../css/s/sba0k3-2g.css';
import '../../css/i/iiid1177w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="sba0k3-2g"/><circle class="iiid1177w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-moonrepo-open" {...props}></Icon>
