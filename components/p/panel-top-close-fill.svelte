<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xorcxlbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xorcxlbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-close-fill" {...props}></Icon>
