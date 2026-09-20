<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv3lvgb1x.css';
import '../../css/l/ldo0svbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3lvgb1x"/><path class="ldo0svbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:lock-opened-light" {...props}></Icon>
