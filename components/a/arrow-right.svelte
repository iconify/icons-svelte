<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfv-sbvh.css';
import '../../css/f/fe3fg-bkg.css';
import '../../css/v/vs3nxnb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzfv-sbvh wm-shadow"/><path class="fe3fg-bkg wm-k"/><path class="vs3nxnb9l wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-right" {...props}></Icon>
