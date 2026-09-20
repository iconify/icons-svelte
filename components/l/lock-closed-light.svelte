<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv3lvgb1x.css';
import '../../css/n/nh7uppbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3lvgb1x"/><path class="nh7uppbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:lock-closed-light" {...props}></Icon>
