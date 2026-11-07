<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgubodb0p.css';
import '../../css/u/uj0gagb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgubodb0p"/><path clip-rule="evenodd" class="uj0gagb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:balloon-outline" {...props}></Icon>
